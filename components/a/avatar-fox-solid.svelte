<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxv98fbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxv98fbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-fox-solid" {...props}></Icon>
