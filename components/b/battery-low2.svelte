<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fk1cwvbyo.css';
import '../../css/j/j246-ubvw.css';
import '../../css/h/huq9i0-2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fk1cwvbyo"/><path clip-rule="evenodd" class="j246-ubvw"/><path class="huq9i0-2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-low2" {...props}></Icon>
