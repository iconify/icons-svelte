<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liqi8irpe.css';
import '../../css/h/hejk39zyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="liqi8irpe"/><circle class="hejk39zyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ionic" {...props}></Icon>
