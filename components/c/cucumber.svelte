<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp2zqlb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":435,"height":512};
const content = `<path clip-rule="evenodd" class="lp2zqlb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cucumber" {...props}></Icon>
