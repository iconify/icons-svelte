<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9m3agbju.css';
import '../../css/z/zc_lys0dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n9m3agbju"/><path clip-rule="evenodd" class="zc_lys0dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:close-single-16" {...props}></Icon>
