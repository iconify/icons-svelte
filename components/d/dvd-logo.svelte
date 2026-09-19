<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd5y7vbjg.css';
import '../../css/x/x5qxkepnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zd5y7vbjg"/><path class="x5qxkepnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:dvd-logo" {...props}></Icon>
