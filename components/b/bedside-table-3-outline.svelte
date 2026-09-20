<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq7e6332b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mq7e6332b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bedside-table-3-outline" {...props}></Icon>
