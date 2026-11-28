<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugva07_4z.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vhklpmewb.css';
import '../../css/y/y1-snpblu.css';
import '../../css/t/t1pug1bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary ugva07_4z"/><g class="dt0cm9dhy primary"><path class="vhklpmewb"/><path class="y1-snpblu"/><path class="t1pug1bay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:first-aid-duo" {...props}></Icon>
