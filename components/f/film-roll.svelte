<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3un3_8gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3un3_8gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:film-roll" {...props}></Icon>
