<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4ulrrbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4ulrrbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mayan-edms-dark" {...props}></Icon>
