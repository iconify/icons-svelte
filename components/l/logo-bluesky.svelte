<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3l-hubpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s3l-hubpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-bluesky" {...props}></Icon>
