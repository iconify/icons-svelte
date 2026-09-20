<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acvtykfex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="acvtykfex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pogocache-dark" {...props}></Icon>
