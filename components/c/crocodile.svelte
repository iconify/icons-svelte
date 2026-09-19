<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r2bgocb9a.css';
import '../../css/f/fne9igb5l.css';
import '../../css/t/tuu7tm3bw.css';
import '../../css/w/wkue1tbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="r2bgocb9a"/><path class="fne9igb5l"/><path class="tuu7tm3bw"/><path class="wkue1tbgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:crocodile" {...props}></Icon>
