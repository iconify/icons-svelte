<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4z3p6btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4z3p6btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-wireless" {...props}></Icon>
