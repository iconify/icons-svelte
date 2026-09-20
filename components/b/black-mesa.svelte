<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j74jll1db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j74jll1db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:black-mesa" {...props}></Icon>
