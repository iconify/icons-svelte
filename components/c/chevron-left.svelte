<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8eprtjec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8eprtjec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-left" {...props}></Icon>
