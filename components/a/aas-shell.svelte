<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu3syowcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu3syowcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell" {...props}></Icon>
