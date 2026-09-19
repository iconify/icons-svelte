<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq2zdxs-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tq2zdxs-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:heading-2" {...props}></Icon>
