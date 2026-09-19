<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i14fa_rsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i14fa_rsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:aliwangwang-fill" {...props}></Icon>
