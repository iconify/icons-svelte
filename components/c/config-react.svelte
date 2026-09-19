<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbsktt95j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbsktt95j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-react" {...props}></Icon>
