<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeo-4db_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeo-4db_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-vertical-fill" {...props}></Icon>
