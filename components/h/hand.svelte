<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v6f07cc4u.css';
import '../../css/f/fj-ipp45f.css';
import '../../css/g/gqos64b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6f07cc4u"/><path class="fj-ipp45f"/><path class="gqos64b9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hand" {...props}></Icon>
