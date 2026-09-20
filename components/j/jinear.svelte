<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_a79lck.css';
import '../../css/d/dwubu5bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md_a79lck"/><path class="dwubu5bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jinear" {...props}></Icon>
