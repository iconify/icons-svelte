<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsz6-0r-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsz6-0r-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dropbox-logo-1-block" {...props}></Icon>
