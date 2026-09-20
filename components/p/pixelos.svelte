<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7yr9bbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="l7yr9bbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pixelos" {...props}></Icon>
