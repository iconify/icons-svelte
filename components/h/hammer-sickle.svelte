<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_8fm84y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd_8fm84y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hammer-sickle" {...props}></Icon>
