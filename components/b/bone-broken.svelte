<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n97-l2bar.css';
import '../../css/b/b94xtzblu.css';
import '../../css/b/b7iizbs3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n97-l2bar"/><path class="b94xtzblu"/><path clip-rule="evenodd" class="b7iizbs3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bone-broken" {...props}></Icon>
