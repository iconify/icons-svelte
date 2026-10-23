<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glfho18fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glfho18fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bug-off" {...props}></Icon>
