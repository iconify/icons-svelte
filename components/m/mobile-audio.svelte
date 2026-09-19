<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_i38kbfh.css';
import '../../css/u/ugyrmsdwo.css';
import '../../css/t/ti3gn7b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a_i38kbfh"/><circle class="ugyrmsdwo"/><path class="ti3gn7b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-audio" {...props}></Icon>
