<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcwdncb4h.css';
import '../../css/t/to1elzbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zcwdncb4h"/><path class="to1elzbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-20" {...props}></Icon>
