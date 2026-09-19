<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acxh3fbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="acxh3fbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:phraseapp" {...props}></Icon>
