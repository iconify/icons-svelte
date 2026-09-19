<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ijc54absg.css';
import '../../css/h/hwda9dbfv.css';
import '../../css/s/stdhzgj1z.css';
import '../../css/d/dw-dkqb5t.css';
import '../../css/a/aa1jcub1d.css';
import '../../css/z/zckpt7bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ijc54absg"/><path class="hwda9dbfv"/><path class="stdhzgj1z"/><path class="dw-dkqb5t"/><path class="aa1jcub1d"/><path class="zckpt7bfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:hyacinth" {...props}></Icon>
