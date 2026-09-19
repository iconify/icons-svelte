<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf0wuc1-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wf0wuc1-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-right" {...props}></Icon>
