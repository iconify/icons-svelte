<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojit29lhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojit29lhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:holy-grail" {...props}></Icon>
