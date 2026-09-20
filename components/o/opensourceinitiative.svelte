<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaeow9b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaeow9b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opensourceinitiative" {...props}></Icon>
