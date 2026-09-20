<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wty3s35uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="wty3s35uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fast-backward-square-f" {...props}></Icon>
