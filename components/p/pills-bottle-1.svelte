<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-kti_wao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-kti_wao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:pills-bottle-1" {...props}></Icon>
