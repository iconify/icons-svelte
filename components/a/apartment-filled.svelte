<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmzwyb1sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmzwyb1sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:apartment-filled" {...props}></Icon>
