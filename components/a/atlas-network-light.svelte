<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oct_aobqd.css';
import '../../css/i/i-8vw9hdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="oct_aobqd"/><path class="i-8vw9hdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atlas-network-light" {...props}></Icon>
