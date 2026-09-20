<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdus7qqaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdus7qqaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:notdef" {...props}></Icon>
