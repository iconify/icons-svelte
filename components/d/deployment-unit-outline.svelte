<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1u7m-bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1u7m-bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:deployment-unit-outline" {...props}></Icon>
