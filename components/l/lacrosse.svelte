<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alnov8bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="alnov8bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:lacrosse" {...props}></Icon>
