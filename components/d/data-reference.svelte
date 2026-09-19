<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gut_bzbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gut_bzbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-reference" {...props}></Icon>
