<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0nzpri2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0nzpri2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cigale" {...props}></Icon>
