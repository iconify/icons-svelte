<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym7iefm2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym7iefm2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:lastfm-logo-solid" {...props}></Icon>
