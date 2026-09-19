<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbiso1wff.css';
import '../../css/y/yhignzrec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mbiso1wff"/><path class="yhignzrec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-evaluation" {...props}></Icon>
