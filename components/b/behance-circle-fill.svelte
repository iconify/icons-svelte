<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx441kbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wx441kbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:behance-circle-fill" {...props}></Icon>
