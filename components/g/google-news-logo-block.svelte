<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpj70b3ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rpj70b3ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-news-logo-block" {...props}></Icon>
