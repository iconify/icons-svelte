<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwh7xgb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwh7xgb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailcow-light" {...props}></Icon>
