<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/akztulxao.css';
import '../../css/i/ie61plbol.css';
import '../../css/c/cma6q9u3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="akztulxao"/><path class="ie61plbol"/><path class="cma6q9u3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:gauge" {...props}></Icon>
