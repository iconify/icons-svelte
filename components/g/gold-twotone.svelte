<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1wxr2brf.css';
import '../../css/x/x6-25tkfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1wxr2brf"/><path class="x6-25tkfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:gold-twotone" {...props}></Icon>
