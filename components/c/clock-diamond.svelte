<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/idlw553oh.css';
import '../../css/i/iddrhtujz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="idlw553oh"/><path class="iddrhtujz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-diamond" {...props}></Icon>
