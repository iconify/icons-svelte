<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/e7ugy10kt.css';
import '../../css/g/gp72obe2t.css';
import '../../css/l/lcts5dtqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7ugy10kt"/><path class="gp72obe2t"/><path class="lcts5dtqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:contact-round" {...props}></Icon>
