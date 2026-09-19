<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhst8qbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nhst8qbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:align-center-outlined" {...props}></Icon>
