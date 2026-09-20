<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd6tf0onp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd6tf0onp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-favorite-outline" {...props}></Icon>
