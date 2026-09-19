<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccug79xbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccug79xbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-coffeescript" {...props}></Icon>
