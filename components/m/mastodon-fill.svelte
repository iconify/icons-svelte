<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_4lxy4yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_4lxy4yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:mastodon-fill" {...props}></Icon>
