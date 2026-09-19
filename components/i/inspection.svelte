<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no_04pbeo.css';
import '../../css/z/zw41ydges.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="no_04pbeo"/><path class="zw41ydges"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:inspection" {...props}></Icon>
