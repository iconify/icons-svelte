<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxys06b2v.css';
import '../../css/k/kju8o8xdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxys06b2v"/><path class="kju8o8xdi ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-logs" {...props}></Icon>
