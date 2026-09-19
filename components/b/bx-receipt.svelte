<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o43zpgbqc.css';
import '../../css/w/w5cu6gb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o43zpgbqc"/><path class="w5cu6gb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-receipt" {...props}></Icon>
