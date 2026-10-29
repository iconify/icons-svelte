<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9sk2mszl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sk2mszl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-right-solid" {...props}></Icon>
