<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/whbuk40qj.css';
import '../../css/c/ctzipybbn.css';
import '../../css/o/oik4ogb9d.css';
import '../../css/h/hn99g3b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="whbuk40qj"/><path class="ctzipybbn"/><path class="oik4ogb9d"/><path class="hn99g3b2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:like-dislike" {...props}></Icon>
