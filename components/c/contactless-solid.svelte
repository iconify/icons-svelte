<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0pt3tdnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0pt3tdnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contactless-solid" {...props}></Icon>
