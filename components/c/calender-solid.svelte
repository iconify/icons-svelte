<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4i1pd5cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4i1pd5cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:calender-solid" {...props}></Icon>
