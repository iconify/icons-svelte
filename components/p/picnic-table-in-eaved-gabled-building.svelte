<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_bwp5i_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t_bwp5i_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table-in-eaved-gabled-building" {...props}></Icon>
