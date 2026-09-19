<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/furgsjbhc.css';
import '../../css/c/cn0c-05yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="furgsjbhc"/><path class="cn0c-05yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-double-right" {...props}></Icon>
