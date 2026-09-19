<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op7gaobel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op7gaobel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-alarm-add" {...props}></Icon>
