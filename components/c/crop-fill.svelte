<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y76ps7bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y76ps7bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:crop-fill" {...props}></Icon>
