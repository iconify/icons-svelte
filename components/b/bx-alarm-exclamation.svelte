<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9f5b6tbj.css';
import '../../css/r/r6aez23ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9f5b6tbj"/><path class="r6aez23ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-alarm-exclamation" {...props}></Icon>
