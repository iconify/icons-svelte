<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot-rahdwk.css';
import '../../css/m/mk7apdhpz.css';
import '../../css/f/fgrlfobbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-rahdwk"/><path class="mk7apdhpz"/><path class="fgrlfobbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:command-bold" {...props}></Icon>
