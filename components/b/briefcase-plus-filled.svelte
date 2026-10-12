<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj2tc7b5c.css';
import '../../css/z/zoxpwbb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tj2tc7b5c"/><path class="zoxpwbb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:briefcase-plus-filled" {...props}></Icon>
