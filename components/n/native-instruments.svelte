<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plqmpyb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":76.1,"height":45};
const content = `<path class="plqmpyb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:native-instruments" {...props}></Icon>
