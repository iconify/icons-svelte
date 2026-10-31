<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/an5k38b2g.css';
import '../../css/q/qw0bn1uiv.css';
import '../../css/c/cpg6xjbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="an5k38b2g"/><path clip-rule="evenodd" class="qw0bn1uiv"/><path clip-rule="evenodd" class="cpg6xjbsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:egg-cell-outline-24px" {...props}></Icon>
