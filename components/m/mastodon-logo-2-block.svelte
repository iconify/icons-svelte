<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g508y9_og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g508y9_og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mastodon-logo-2-block" {...props}></Icon>
