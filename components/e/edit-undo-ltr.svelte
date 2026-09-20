<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot_dhmbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ot_dhmbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:edit-undo-ltr" {...props}></Icon>
