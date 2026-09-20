<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4w_dm9xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4w_dm9xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-check-outline" {...props}></Icon>
