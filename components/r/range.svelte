<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1vsmrbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":4};
const content = `<path class="x1vsmrbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:range" {...props}></Icon>
