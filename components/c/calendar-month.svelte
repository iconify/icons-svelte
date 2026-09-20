<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ainr45o9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ainr45o9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:calendar-month" {...props}></Icon>
