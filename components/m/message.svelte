<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzy0c9c2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzy0c9c2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message" {...props}></Icon>
