<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj1cvqbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="nj1cvqbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:calendar-split" {...props}></Icon>
