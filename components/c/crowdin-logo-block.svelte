<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3pj0pbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3pj0pbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:crowdin-logo-block" {...props}></Icon>
