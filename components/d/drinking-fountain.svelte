<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er8u5db2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="er8u5db2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:drinking-fountain" {...props}></Icon>
