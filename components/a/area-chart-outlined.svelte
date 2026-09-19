<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-2451v-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q-2451v-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:area-chart-outlined" {...props}></Icon>
