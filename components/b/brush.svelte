<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/d/d9kplxbfn.css';
import '../../css/a/a5r5lvb1n.css';
import '../../css/p/plpw9sb1i.css';
import '../../css/b/b6cya0bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="d9kplxbfn"/><path class="a5r5lvb1n"/><path class="plpw9sb1i"/><path class="b6cya0bdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:brush" {...props}></Icon>
