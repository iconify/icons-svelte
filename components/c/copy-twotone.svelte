<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro6hirbas.css';
import '../../css/o/o9_y2yslb.css';
import '../../css/y/y_23wccrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ro6hirbas"/><path class="o9_y2yslb"/><path class="y_23wccrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:copy-twotone" {...props}></Icon>
