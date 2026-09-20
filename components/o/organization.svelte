<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shr8w08ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="shr8w08ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:organization" {...props}></Icon>
