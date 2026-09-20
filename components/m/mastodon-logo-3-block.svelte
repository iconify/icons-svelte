<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6gw00hkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z6gw00hkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mastodon-logo-3-block" {...props}></Icon>
