<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyi5vz6mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyi5vz6mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-up-line" {...props}></Icon>
