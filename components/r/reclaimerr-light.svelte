<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-93l-57t.css';
import '../../css/c/cgqm05v5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-93l-57t"/><path class="cgqm05v5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reclaimerr-light" {...props}></Icon>
