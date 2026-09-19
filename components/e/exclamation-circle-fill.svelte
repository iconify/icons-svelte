<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js2wifbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="js2wifbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:exclamation-circle-fill" {...props}></Icon>
