<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq-4co-2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vq-4co-2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:amazon-outlined" {...props}></Icon>
