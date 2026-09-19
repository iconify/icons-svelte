<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4_tterzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i4_tterzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:borderless-table-outlined" {...props}></Icon>
