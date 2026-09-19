<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9x_81bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e9x_81bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:loading-3-quarters-outline" {...props}></Icon>
