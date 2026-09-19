<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/dbmfimb0q.css';
import '../../css/l/l5y23ru5w.css';
import '../../css/a/axu8vacgl.css';
import '../../css/k/kouxvgbln.css';
import '../../css/g/gzzcnbppf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="dbmfimb0q"/><g class="l5y23ru5w"><path class="axu8vacgl"/><path class="kouxvgbln"/><path class="gzzcnbppf"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:eth" {...props}></Icon>
