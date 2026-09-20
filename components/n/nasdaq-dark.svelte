<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxgzcwb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxgzcwb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasdaq-dark" {...props}></Icon>
