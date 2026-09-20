<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjd7c4bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjd7c4bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fleet-dm-dark" {...props}></Icon>
