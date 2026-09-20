<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mi9gqvjwc.css';
import '../../css/o/ohm0zoruo.css';
import '../../css/m/ma09lhbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mi9gqvjwc"/><path class="ohm0zoruo"/><path class="ma09lhbyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:drink" {...props}></Icon>
