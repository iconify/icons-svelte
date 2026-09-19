<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm1g5qbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fm1g5qbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-left-to-line" {...props}></Icon>
