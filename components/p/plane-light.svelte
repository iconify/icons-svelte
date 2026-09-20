<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah_305bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ah_305bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plane-light" {...props}></Icon>
