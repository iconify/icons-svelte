<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbdb5tbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbdb5tbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:right-to-left-list-triangle" {...props}></Icon>
