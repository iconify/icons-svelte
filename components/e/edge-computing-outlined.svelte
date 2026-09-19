<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpdpley1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpdpley1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:edge-computing-outlined" {...props}></Icon>
