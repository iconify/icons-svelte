<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehdnanaqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehdnanaqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailflow-sh-light" {...props}></Icon>
