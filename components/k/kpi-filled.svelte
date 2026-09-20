<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1pf-3hdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f1pf-3hdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:kpi-filled" {...props}></Icon>
