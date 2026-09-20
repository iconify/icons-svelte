<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezfumgw-x.css';
import '../../css/z/z3zqi1lzk.css';
import '../../css/b/brsl2mb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ezfumgw-x"><path class="z3zqi1lzk"/><path class="brsl2mb1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-turn-down-large" {...props}></Icon>
