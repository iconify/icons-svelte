<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez1wi6bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ez1wi6bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-long-outline" {...props}></Icon>
