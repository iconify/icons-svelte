<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ori6jp11a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ori6jp11a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ranch-gate" {...props}></Icon>
