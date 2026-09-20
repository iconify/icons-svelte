<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2cr00brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m2cr00brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nagios-light" {...props}></Icon>
