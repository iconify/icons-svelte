<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2r6-ab1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="y2r6-ab1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:mastodon" {...props}></Icon>
