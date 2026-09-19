<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izll3ybxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izll3ybxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-6" {...props}></Icon>
