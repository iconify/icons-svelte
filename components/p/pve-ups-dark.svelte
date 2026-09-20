<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6br75yqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6br75yqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pve-ups-dark" {...props}></Icon>
