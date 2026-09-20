<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rb_6zxbcl.css';
import '../../css/u/u2gjaigap.css';
import '../../css/m/mvn6bybtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rb_6zxbcl"/><path class="u2gjaigap"/><path class="mvn6bybtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-search-filled" {...props}></Icon>
