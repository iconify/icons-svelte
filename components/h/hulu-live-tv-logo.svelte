<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b05ho5hmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b05ho5hmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:hulu-live-tv-logo" {...props}></Icon>
