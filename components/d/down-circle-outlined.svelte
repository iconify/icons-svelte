<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f33c5bbfy.css';
import '../../css/y/yv_brepse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f33c5bbfy"/><path class="yv_brepse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:down-circle-outlined" {...props}></Icon>
