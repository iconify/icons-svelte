<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/u1b612b-s.css';
import '../../css/z/zb6ugnr2e.css';
import '../../css/e/ey9qgmrtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="u1b612b-s"/><path class="zb6ugnr2e"/><path class="ey9qgmrtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:git-commit" {...props}></Icon>
