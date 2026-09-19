<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkjpt4ruz.css';
import '../../css/x/xoqcm6b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lkjpt4ruz"/><path class="xoqcm6b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-edit" {...props}></Icon>
