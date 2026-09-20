<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3qhq9u6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w3qhq9u6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hard-drive-1-solid" {...props}></Icon>
