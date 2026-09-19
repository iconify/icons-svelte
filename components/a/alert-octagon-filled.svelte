<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgx4pib1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgx4pib1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-octagon-filled" {...props}></Icon>
