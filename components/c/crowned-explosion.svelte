<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycc1cgbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ycc1cgbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crowned-explosion" {...props}></Icon>
