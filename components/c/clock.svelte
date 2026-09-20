<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efr-ryaff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="efr-ryaff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:clock" {...props}></Icon>
