<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh810pbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="eh810pbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dice-six" {...props}></Icon>
