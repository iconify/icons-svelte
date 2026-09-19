<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-cy1ebpm.css';
import '../../css/m/miw977k3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-cy1ebpm"/><path class="miw977k3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-box" {...props}></Icon>
