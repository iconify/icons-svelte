<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5wag-rzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x5wag-rzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:rotate-right" {...props}></Icon>
