<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8cmkxbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g8cmkxbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:linux-outlined" {...props}></Icon>
