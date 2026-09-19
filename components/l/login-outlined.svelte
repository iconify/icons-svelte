<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj665y5jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fj665y5jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:login-outlined" {...props}></Icon>
