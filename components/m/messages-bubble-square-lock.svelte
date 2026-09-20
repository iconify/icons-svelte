<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6r127bgj.css';
import '../../css/e/e7r56mbuj.css';
import '../../css/q/qs_8itbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6r127bgj"/><path class="e7r56mbuj"/><path class="qs_8itbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-square-lock" {...props}></Icon>
