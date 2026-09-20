<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s08wsdt4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s08wsdt4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openzfs-dark" {...props}></Icon>
