<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un6mu3bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="un6mu3bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cbl" {...props}></Icon>
