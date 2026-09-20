<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x21i0yv0u.css';
import '../../css/h/hcnco5bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x21i0yv0u"/><path class="hcnco5bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-actions-check-1-bold" {...props}></Icon>
