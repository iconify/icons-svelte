<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0v59wb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z0v59wb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:copy-check-xmark" {...props}></Icon>
