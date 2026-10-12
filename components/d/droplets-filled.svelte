<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjc5x9bqo.css';
import '../../css/o/oevx49bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjc5x9bqo"/><path class="oevx49bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:droplets-filled" {...props}></Icon>
