<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp0yuxb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp0yuxb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-up" {...props}></Icon>
