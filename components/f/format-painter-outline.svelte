<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3qz6_b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3qz6_b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:format-painter-outline" {...props}></Icon>
