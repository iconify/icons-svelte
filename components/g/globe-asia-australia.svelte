<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf-uribdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf-uribdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-asia-australia" {...props}></Icon>
