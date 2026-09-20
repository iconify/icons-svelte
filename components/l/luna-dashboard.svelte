<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uan11fboz.css';
import '../../css/n/ng3jq3bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uan11fboz"/><path class="ng3jq3bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:luna-dashboard" {...props}></Icon>
