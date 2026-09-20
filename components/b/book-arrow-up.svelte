<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g73jhjbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g73jhjbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-arrow-up" {...props}></Icon>
