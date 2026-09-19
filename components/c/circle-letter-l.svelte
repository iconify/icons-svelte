<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc0419z2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bc0419z2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-l" {...props}></Icon>
