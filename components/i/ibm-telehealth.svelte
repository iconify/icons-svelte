<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkg334b8z.css';
import '../../css/r/r3uwgacnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gkg334b8z"/><path class="r3uwgacnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-telehealth" {...props}></Icon>
