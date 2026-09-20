<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh85zl5bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uh85zl5bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intelowl-light" {...props}></Icon>
