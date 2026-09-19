<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlrk4-bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nlrk4-bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:pin" {...props}></Icon>
