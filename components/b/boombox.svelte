<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah5mw8brc.css';
import '../../css/t/tsy_4oboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah5mw8brc"/><path class="tsy_4oboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:boombox" {...props}></Icon>
