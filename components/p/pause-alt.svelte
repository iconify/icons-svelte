<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsfu-mu3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rsfu-mu3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:pause-alt" {...props}></Icon>
