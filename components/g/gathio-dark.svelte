<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pojcwywxn.css';
import '../../css/h/hua_nkb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pojcwywxn"/><path class="hua_nkb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gathio-dark" {...props}></Icon>
