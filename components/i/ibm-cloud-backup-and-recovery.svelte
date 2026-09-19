<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6n2pebht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b6n2pebht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-backup-and-recovery" {...props}></Icon>
