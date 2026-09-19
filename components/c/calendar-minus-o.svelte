<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mag9m6fqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="mag9m6fqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:calendar-minus-o" {...props}></Icon>
