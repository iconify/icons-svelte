<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhog3w6ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhog3w6ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-talk-logo-block" {...props}></Icon>
