<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpds53b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpds53b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mastodon-fill-16" {...props}></Icon>
