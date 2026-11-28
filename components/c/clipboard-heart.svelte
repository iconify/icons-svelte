<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bu_5_sd4o.css';
import '../../css/j/jjy36xb2g.css';
import '../../css/i/i29sr3qkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bu_5_sd4o"/><path class="jjy36xb2g"/><path class="i29sr3qkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clipboard-heart" {...props}></Icon>
