<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/objfwp1iv.css';
import '../../css/a/ao1eykxlw.css';
import '../../css/h/hod5p82lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="objfwp1iv"/><path class="ao1eykxlw"/><path class="hod5p82lh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:electric-tower-02" {...props}></Icon>
