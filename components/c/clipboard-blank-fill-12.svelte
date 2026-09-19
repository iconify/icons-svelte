<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmb67ktsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mmb67ktsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-blank-fill-12" {...props}></Icon>
