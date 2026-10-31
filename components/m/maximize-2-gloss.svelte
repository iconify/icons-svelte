<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0iyle_8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0iyle_8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:maximize-2-gloss" {...props}></Icon>
