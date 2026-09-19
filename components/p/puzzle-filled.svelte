<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5024nbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5024nbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:puzzle-filled" {...props}></Icon>
