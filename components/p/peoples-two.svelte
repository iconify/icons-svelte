<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwsj9qblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bwsj9qblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:peoples-two" {...props}></Icon>
