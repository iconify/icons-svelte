<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_rj89vzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_rj89vzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:border-right-outlined" {...props}></Icon>
