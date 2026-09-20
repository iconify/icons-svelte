<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oor-few0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oor-few0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relic-storage-light" {...props}></Icon>
