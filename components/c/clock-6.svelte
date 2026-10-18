<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2lduos0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2lduos0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clock-6" {...props}></Icon>
