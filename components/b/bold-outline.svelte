<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8ts7hg1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b8ts7hg1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bold-outline" {...props}></Icon>
