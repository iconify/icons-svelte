<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/cgm86oegm.css';
import '../../css/j/jsjb8tb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgm86oegm"/><path class="jsjb8tb2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-4-square-light" {...props}></Icon>
