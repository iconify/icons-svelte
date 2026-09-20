<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0a6sbcax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="e0a6sbcax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bbq-11" {...props}></Icon>
