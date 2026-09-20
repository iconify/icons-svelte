<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/yy_lm7s2u.css';
import '../../css/b/bz-kqsi4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yy_lm7s2u"/><path class="bz-kqsi4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-bottombar-expand" {...props}></Icon>
