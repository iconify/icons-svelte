<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l30n8pb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l30n8pb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filerise-dark" {...props}></Icon>
