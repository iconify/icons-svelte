<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x738439pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x738439pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:champagne-filled" {...props}></Icon>
