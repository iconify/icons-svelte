<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul0z0lfqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul0z0lfqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart-circle-filled" {...props}></Icon>
