<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmbihr2qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bmbihr2qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-interrupt" {...props}></Icon>
