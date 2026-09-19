<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi1n5xsqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hi1n5xsqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:house" {...props}></Icon>
