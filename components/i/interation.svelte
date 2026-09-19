<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmj63msac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nmj63msac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:interation" {...props}></Icon>
