<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjxop5ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lrjxop5ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:hourglass" {...props}></Icon>
