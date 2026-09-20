<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/royomp97n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="royomp97n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-check-multiple-outline" {...props}></Icon>
