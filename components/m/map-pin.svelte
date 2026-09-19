<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g8089ybkd.css';
import '../../css/u/uc-p4fbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g8089ybkd"/><path class="uc-p4fbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:map-pin" {...props}></Icon>
