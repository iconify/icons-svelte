<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwur3-bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwur3-bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:event-edit" {...props}></Icon>
