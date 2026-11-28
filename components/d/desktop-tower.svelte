<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f87hdkbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f87hdkbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:desktop-tower" {...props}></Icon>
