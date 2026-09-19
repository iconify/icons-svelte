<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irbdrs3va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="irbdrs3va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:copyright-outlined" {...props}></Icon>
