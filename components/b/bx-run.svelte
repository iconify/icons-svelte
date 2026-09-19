<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aovzl8biz.css';
import '../../css/o/oj1pjebiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="aovzl8biz"/><path class="oj1pjebiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-run" {...props}></Icon>
