<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dau6xu-gm.css';
import '../../css/i/ih0df-bqd.css';
import '../../css/i/i4uqfac5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dau6xu-gm"/><rect class="ih0df-bqd"/><path class="i4uqfac5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:calibrated-meter" {...props}></Icon>
