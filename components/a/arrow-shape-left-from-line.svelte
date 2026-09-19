<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9tofuw_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n9tofuw_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-left-from-line" {...props}></Icon>
