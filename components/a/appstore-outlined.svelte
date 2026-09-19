<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5niq8rsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p5niq8rsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:appstore-outlined" {...props}></Icon>
