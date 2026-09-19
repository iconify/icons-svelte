<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfzo6ykko.css';
import '../../css/i/i7bhdq50x.css';
import '../../css/f/f3b7m4bwr.css';
import '../../css/i/idr62cb8i.css';
import '../../css/a/a6bu6ybyo.css';
import '../../css/l/lewl3tckg.css';
import '../../css/r/rp_y-zbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfzo6ykko"/><path class="i7bhdq50x"/><path class="f3b7m4bwr"/><path class="idr62cb8i"/><path class="a6bu6ybyo"/><path class="lewl3tckg"/><path class="rp_y-zbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:automobile" {...props}></Icon>
