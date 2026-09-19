<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zacvbf9rr.css';
import '../../css/b/bex3sxi3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zacvbf9rr"/><path class="bex3sxi3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:funnel-plot-twotone" {...props}></Icon>
