<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpjo1kt9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpjo1kt9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-balloon-gloss" {...props}></Icon>
