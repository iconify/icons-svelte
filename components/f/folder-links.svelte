<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed5_uy-8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed5_uy-8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-links" {...props}></Icon>
