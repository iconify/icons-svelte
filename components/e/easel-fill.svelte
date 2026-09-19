<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn2mq9eik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zn2mq9eik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:easel-fill" {...props}></Icon>
