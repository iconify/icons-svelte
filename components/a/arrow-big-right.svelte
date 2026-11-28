<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgfy8elcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgfy8elcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-right" {...props}></Icon>
