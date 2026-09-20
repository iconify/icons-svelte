<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9s3m40bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a9s3m40bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-tray-1-solid" {...props}></Icon>
