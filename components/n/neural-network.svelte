<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh_xxntfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh_xxntfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:neural-network" {...props}></Icon>
