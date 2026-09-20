<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpoxny2nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpoxny2nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-pause" {...props}></Icon>
