<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a92y3xrqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a92y3xrqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:id-card" {...props}></Icon>
