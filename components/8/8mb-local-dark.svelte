<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8f3r6nli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8f3r6nli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:8mb-local-dark" {...props}></Icon>
