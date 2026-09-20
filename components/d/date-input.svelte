<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mut1umbgi.css';
import '../../css/g/g3-s662on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mut1umbgi"/><path class="g3-s662on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:date-input" {...props}></Icon>
