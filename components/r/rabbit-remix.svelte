<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u82v2_bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u82v2_bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:rabbit-remix" {...props}></Icon>
