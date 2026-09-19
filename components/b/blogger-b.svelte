<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmdgq1b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zmdgq1b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:blogger-b" {...props}></Icon>
