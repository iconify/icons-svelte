<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3onnwugn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3onnwugn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:khan-academy" {...props}></Icon>
