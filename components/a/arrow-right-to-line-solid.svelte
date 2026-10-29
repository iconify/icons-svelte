<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrcg_m-ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrcg_m-ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-right-to-line-solid" {...props}></Icon>
