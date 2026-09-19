<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxmk_0bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zxmk_0bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:good-one" {...props}></Icon>
