<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o--qnccve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1515,"height":1477};
const content = `<path class="o--qnccve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nordea-light" {...props}></Icon>
