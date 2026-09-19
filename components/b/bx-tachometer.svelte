<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t02myt54b.css';
import '../../css/n/nco21hbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t02myt54b"/><path class="nco21hbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-tachometer" {...props}></Icon>
