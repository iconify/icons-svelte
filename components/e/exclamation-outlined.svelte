<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iby7qcc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iby7qcc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:exclamation-outlined" {...props}></Icon>
