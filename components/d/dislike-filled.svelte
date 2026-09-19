<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlnai6byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hlnai6byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dislike-filled" {...props}></Icon>
