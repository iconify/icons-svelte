<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyalztbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wyalztbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:prescription-pills-drugs-healthcare" {...props}></Icon>
