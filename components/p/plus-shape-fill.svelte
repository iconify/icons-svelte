<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez-3s-a2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ez-3s-a2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:plus-shape-fill" {...props}></Icon>
