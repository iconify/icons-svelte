<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0lvo7bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0lvo7bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portracker-dark" {...props}></Icon>
