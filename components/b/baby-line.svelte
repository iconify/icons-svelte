<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy-g8lbjc.css';
import '../../css/c/c_jcusmko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-g8lbjc"/><path class="c_jcusmko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baby-line" {...props}></Icon>
