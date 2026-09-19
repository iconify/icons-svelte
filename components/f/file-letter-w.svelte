<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl6idlb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bl6idlb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-letter-w" {...props}></Icon>
