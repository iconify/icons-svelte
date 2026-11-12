<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohrnp0dwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ohrnp0dwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:osticket-light" {...props}></Icon>
