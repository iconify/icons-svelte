<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4fyvha9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a4fyvha9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dot-chart-outlined" {...props}></Icon>
