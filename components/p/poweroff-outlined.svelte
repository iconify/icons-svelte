<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvopk5nyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bvopk5nyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:poweroff-outlined" {...props}></Icon>
