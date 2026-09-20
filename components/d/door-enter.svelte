<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ohd3mqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ohd3mqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:door-enter" {...props}></Icon>
