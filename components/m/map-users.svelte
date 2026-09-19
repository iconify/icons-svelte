<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br3iyqaeh.css';
import '../../css/g/gng30g8lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="br3iyqaeh"/><path class="gng30g8lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-users" {...props}></Icon>
