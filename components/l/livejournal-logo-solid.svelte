<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4ruh3b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4ruh3b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:livejournal-logo-solid" {...props}></Icon>
