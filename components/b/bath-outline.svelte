<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy8rzb4wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vy8rzb4wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bath-outline" {...props}></Icon>
