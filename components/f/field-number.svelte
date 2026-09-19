<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp-_rmb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cp-_rmb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:field-number" {...props}></Icon>
