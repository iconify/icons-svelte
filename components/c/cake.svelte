<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/o/o7nvpq57o.css';
import '../../css/f/f30pbdbez.css';
import '../../css/o/ohyczpkjk.css';
import '../../css/w/w_fx7s3su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="o7nvpq57o"/><path class="f30pbdbez"/><path class="ohyczpkjk"/><path class="w_fx7s3su"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cake" {...props}></Icon>
