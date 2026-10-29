<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p16a97b5q.css';
import '../../css/c/c-rpqrb2u.css';
import '../../css/i/ii6dtkbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p16a97b5q wm-k"/><path class="c-rpqrb2u wm-shadow"/><path class="ii6dtkbwz wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-merge-engrave" {...props}></Icon>
