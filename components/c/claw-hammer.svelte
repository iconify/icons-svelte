<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eog32eskm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eog32eskm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:claw-hammer" {...props}></Icon>
