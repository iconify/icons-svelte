<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os1_vdd3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="os1_vdd3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ourschool-dark" {...props}></Icon>
