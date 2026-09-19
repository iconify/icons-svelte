<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnjr8vb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":32};
const content = `<path class="fnjr8vb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:beaker" {...props}></Icon>
