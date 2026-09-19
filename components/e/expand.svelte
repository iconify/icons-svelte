<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1kmpjbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r1kmpjbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:expand" {...props}></Icon>
