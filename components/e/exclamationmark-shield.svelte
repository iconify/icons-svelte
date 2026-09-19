<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3jmpsbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="p3jmpsbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:exclamationmark-shield" {...props}></Icon>
