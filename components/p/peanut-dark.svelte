<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb-mk4b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eb-mk4b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peanut-dark" {...props}></Icon>
