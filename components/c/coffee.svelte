<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fj1bz4bph.css';
import '../../css/g/g78h_ubkd.css';
import '../../css/j/jh_igqb8n.css';
import '../../css/f/f_gq_5bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fj1bz4bph wm-shadow"/><path class="g78h_ubkd wm-shadow"/><path class="jh_igqb8n"/><path class="f_gq_5bhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:coffee" {...props}></Icon>
