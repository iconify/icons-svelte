<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1cpmz2ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l1cpmz2ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gastroenterology" {...props}></Icon>
