<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo14xkb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo14xkb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mayan-edms-dark" {...props}></Icon>
