<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll22o1baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ll22o1baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:alipay-circle-outlined" {...props}></Icon>
