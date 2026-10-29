<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5c1yxb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5c1yxb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-vertical-solid" {...props}></Icon>
