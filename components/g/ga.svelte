<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lpmwpmbjx.css';
import '../../css/g/gofpikhwp.css';
import '../../css/y/ydhv3dbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lpmwpmbjx"/><path class="gofpikhwp"/><path class="ydhv3dbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:ga" {...props}></Icon>
