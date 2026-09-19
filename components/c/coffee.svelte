<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok0x02bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ok0x02bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:coffee" {...props}></Icon>
