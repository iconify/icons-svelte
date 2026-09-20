<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6hztubmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t6hztubmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:retweet-solid" {...props}></Icon>
