<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwh12uzbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":61};
const content = `<path class="rwh12uzbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cityflo" {...props}></Icon>
