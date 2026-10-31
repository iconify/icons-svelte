<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkoaw5bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkoaw5bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mastodon-fill-round" {...props}></Icon>
