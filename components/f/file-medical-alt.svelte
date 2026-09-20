<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if8ou1ogq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="if8ou1ogq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-medical-alt" {...props}></Icon>
