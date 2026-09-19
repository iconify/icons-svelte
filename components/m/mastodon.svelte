<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqirhidul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xqirhidul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mastodon" {...props}></Icon>
