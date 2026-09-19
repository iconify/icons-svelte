<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdsn85ysj.css';
import '../../css/x/xk4xuvuka.css';
import '../../css/x/xfngl4bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdsn85ysj"/><path class="xk4xuvuka"/><path class="xfngl4bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:radio-outline" {...props}></Icon>
