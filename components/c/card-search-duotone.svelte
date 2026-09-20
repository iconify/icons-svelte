<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d9hh3_5nb.css';
import '../../css/m/mvn6bybtl.css';
import '../../css/r/rb_6zxbcl.css';
import '../../css/u/uped8l_dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d9hh3_5nb"/><path class="mvn6bybtl"/><path clip-rule="evenodd" class="rb_6zxbcl"/><path class="uped8l_dw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-search-duotone" {...props}></Icon>
