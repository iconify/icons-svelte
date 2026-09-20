<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqm994blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqm994blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:package" {...props}></Icon>
