<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cusyfrbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cusyfrbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:drop-up" {...props}></Icon>
