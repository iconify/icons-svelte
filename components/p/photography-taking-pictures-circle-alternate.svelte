<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezcxgba8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezcxgba8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-taking-pictures-circle-alternate" {...props}></Icon>
