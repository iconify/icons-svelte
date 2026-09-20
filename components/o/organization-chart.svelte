<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdf_ixb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdf_ixb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:organization-chart" {...props}></Icon>
