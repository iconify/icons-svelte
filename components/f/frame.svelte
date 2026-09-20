<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru7if7xhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru7if7xhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:frame" {...props}></Icon>
