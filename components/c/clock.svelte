<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7crpz2ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7crpz2ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock" {...props}></Icon>
