<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5c2ixb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5c2ixb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pentagon-minus" {...props}></Icon>
