<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgam3xbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tgam3xbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dropbox-solid" {...props}></Icon>
