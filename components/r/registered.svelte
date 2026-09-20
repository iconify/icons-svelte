<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2eb7qbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2eb7qbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:registered" {...props}></Icon>
