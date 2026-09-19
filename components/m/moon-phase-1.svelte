<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhg0jyb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhg0jyb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-1" {...props}></Icon>
