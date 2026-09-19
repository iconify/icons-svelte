<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/x/xvfjjxbtd.css';
import '../../css/v/vrq-bdbyc.css';
import '../../css/v/v7lcw7jtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xvfjjxbtd"/><path class="vrq-bdbyc"/><path class="v7lcw7jtd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cable" {...props}></Icon>
