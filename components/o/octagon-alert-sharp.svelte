<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/u/up15_y9jb.css';
import '../../css/j/j_efvl6tx.css';
import '../../css/z/zs843lqwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="up15_y9jb"/><path class="j_efvl6tx"/><path class="zs843lqwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:octagon-alert-sharp" {...props}></Icon>
