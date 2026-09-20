<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o361ukbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o361ukbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-alt-2-line" {...props}></Icon>
