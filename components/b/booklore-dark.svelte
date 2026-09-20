<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn203wbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gn203wbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:booklore-dark" {...props}></Icon>
