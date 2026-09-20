<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enk1d3she.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="enk1d3she"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:database-filled" {...props}></Icon>
