<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2mfls2pl.css';
import '../../css/v/v9ltn1t8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v2mfls2pl"/><path class="v9ltn1t8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:log-out-ltr" {...props}></Icon>
