<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bru927b7a.css';
import '../../css/t/tibham96p.css';
import '../../css/n/nvyrcxbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="bru927b7a"/><path class="tibham96p"/><path class="nvyrcxbrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:friendli" {...props}></Icon>
