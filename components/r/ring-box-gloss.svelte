<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi1hhvbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi1hhvbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ring-box-gloss" {...props}></Icon>
