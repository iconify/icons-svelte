<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt3t3qzmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt3t3qzmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:omarchy" {...props}></Icon>
