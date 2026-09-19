<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4e87f__o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z4e87f__o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-transfer-fill-16" {...props}></Icon>
