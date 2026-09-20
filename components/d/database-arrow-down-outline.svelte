<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8t1gyelg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8t1gyelg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-arrow-down-outline" {...props}></Icon>
