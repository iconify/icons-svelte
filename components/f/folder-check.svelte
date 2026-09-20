<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yyao8-oxf.css';
import '../../css/z/zsfsp97yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyao8-oxf"/><path class="zsfsp97yi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-check" {...props}></Icon>
