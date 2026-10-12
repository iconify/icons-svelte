<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph626sk7j.css';
import '../../css/p/p3y5o8bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph626sk7j"/><path class="p3y5o8bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mic-filled" {...props}></Icon>
