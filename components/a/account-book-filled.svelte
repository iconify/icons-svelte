<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djrt-nrht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="djrt-nrht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:account-book-filled" {...props}></Icon>
