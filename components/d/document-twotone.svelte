<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co7uwg.css';
import '../../css/p/p-fhbk.css';
import '../../css/q/qa-o7h.css';
import '../../css/a/ab0nvj.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co7uwg"/><path class="p-fhbk qa-o7h"/><path class="ab0nvj qa-o7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:document-twotone" {...props}></Icon>
