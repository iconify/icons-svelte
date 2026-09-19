<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf9hn5q-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="cf9hn5q-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:github-alt" {...props}></Icon>
