<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anmx89xew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anmx89xew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-swap-horizontal-filled" {...props}></Icon>
