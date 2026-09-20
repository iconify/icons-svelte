<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttxv75bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttxv75bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paper-jam" {...props}></Icon>
