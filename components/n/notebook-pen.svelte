<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-0nzsqfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-0nzsqfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:notebook-pen" {...props}></Icon>
