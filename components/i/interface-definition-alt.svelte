<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my5n0s3xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="my5n0s3xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:interface-definition-alt" {...props}></Icon>
