<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq7_-sb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="aq7_-sb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-sun-rain-fill" {...props}></Icon>
