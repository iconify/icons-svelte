<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za5ojpbbz.css';
import '../../css/t/tdrcj_yxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="za5ojpbbz"/><path class="tdrcj_yxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-table" {...props}></Icon>
