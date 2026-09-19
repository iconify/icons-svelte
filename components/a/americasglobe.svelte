<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic6wf_bti.css';
import '../../css/h/h-x55eb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ic6wf_bti"/><path class="h-x55eb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:americasglobe" {...props}></Icon>
