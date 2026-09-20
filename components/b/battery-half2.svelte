<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h-xldtp5u.css';
import '../../css/y/yhp6z-bco.css';
import '../../css/h/huq9i0-2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h-xldtp5u"/><path clip-rule="evenodd" class="yhp6z-bco"/><path class="huq9i0-2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-half2" {...props}></Icon>
