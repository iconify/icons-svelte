<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr5_v4qbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gr5_v4qbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-up" {...props}></Icon>
