<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_gugabas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_gugabas wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-person-glasses-gloss" {...props}></Icon>
