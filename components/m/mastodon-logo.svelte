<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8n-h5bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z8n-h5bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mastodon-logo" {...props}></Icon>
