<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drr_rdr2u.css';
import '../../css/j/jw6etd-fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drr_rdr2u"/><path class="jw6etd-fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:chart-pie-solid" {...props}></Icon>
