<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxa1debtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="hxa1debtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:95-200" {...props}></Icon>
