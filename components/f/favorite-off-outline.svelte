<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb_3_72qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb_3_72qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-off-outline" {...props}></Icon>
