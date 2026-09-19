<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn0wn_bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cn0wn_bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:radar-chart-outline" {...props}></Icon>
