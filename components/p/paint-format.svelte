<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnrb4wbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xnrb4wbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:paint-format" {...props}></Icon>
