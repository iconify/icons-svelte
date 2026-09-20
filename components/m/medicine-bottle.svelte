<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu70gxb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu70gxb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:medicine-bottle" {...props}></Icon>
