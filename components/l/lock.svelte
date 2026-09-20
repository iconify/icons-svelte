<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f964tccdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="f964tccdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:lock" {...props}></Icon>
