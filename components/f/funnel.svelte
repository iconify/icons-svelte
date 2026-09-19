<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou-9p9brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ou-9p9brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:funnel" {...props}></Icon>
