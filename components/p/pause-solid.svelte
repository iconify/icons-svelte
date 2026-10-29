<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqmqlk5qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqmqlk5qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pause-solid" {...props}></Icon>
