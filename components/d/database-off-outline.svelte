<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq5gymbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq5gymbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-off-outline" {...props}></Icon>
