<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l469j5b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l469j5b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-edit-outline" {...props}></Icon>
