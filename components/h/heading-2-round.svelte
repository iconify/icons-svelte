<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h57vfdbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h57vfdbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-2-round" {...props}></Icon>
