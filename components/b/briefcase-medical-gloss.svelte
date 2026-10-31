<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvngmp3sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvngmp3sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-medical-gloss" {...props}></Icon>
