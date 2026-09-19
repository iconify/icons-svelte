<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1_2z9bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="a1_2z9bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hate" {...props}></Icon>
