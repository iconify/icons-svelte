<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk_tm6ard.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tk_tm6ard"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:input-latin-lower-letters" {...props}></Icon>
