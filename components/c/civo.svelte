<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab1a5obfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab1a5obfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:civo" {...props}></Icon>
