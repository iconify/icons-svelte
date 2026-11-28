<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyvavccsv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bftptrbtp.css';
import '../../css/w/wn6e618bi.css';
import '../../css/i/i0b60i0dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyvavccsv secondary"/><g class="dt0cm9dhy primary"><path class="bftptrbtp"/><path class="wn6e618bi"/><path class="i0b60i0dz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pizza-duo" {...props}></Icon>
