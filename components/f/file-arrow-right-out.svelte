<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8veo69iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u8veo69iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-arrow-right-out" {...props}></Icon>
