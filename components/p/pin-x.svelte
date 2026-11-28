<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-1ckvb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-1ckvb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pin-x" {...props}></Icon>
