<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo_x6wbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo_x6wbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-haskell" {...props}></Icon>
