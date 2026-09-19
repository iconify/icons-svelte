<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/s/sol3rjohs.css';
import '../../css/e/emikm_bht.css';
import '../../css/d/d5_mhobqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><circle class="sol3rjohs"/><path class="emikm_bht"/><path class="d5_mhobqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:frowning-face" {...props}></Icon>
