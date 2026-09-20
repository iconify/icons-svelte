<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhoq_e62f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bhoq_e62f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:macrumors-dark" {...props}></Icon>
