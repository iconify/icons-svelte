<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yew2c0sjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yew2c0sjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-mastodon" {...props}></Icon>
