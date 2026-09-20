<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzlwo8b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzlwo8b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-beats-logo-block" {...props}></Icon>
