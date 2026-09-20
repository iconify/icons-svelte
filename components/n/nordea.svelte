<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j13sb7b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1515,"height":1477};
const content = `<path class="j13sb7b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nordea" {...props}></Icon>
