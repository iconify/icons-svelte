<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um5hbmb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="um5hbmb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mail-fill" {...props}></Icon>
