<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3n8v4ttr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3n8v4ttr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:books" {...props}></Icon>
