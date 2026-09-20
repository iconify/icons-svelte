<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry6fhv99o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry6fhv99o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-pound-off" {...props}></Icon>
