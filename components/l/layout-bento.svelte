<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f3326pq5l.css';
import '../../css/l/lnuqcu1vn.css';
import '../../css/o/o6rrpwbqi.css';
import '../../css/q/qhiifsb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f3326pq5l"/><path class="lnuqcu1vn"/><path class="o6rrpwbqi"/><path class="qhiifsb6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layout-bento" {...props}></Icon>
