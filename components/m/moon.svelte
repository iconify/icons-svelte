<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9n7sgaal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9n7sgaal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:moon" {...props}></Icon>
