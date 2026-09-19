<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y21lb_bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y21lb_bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dashboard-fill" {...props}></Icon>
