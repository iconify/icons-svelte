<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy3p889il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yy3p889il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad" {...props}></Icon>
