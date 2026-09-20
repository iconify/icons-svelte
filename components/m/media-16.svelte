<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj2y_opli.css';
import '../../css/k/klmk3-lhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wj2y_opli"/><path clip-rule="evenodd" class="klmk3-lhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:media-16" {...props}></Icon>
