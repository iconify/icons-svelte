<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzfrs0mvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zzfrs0mvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:desktop-computer" {...props}></Icon>
