<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqiuyz00l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqiuyz00l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-line" {...props}></Icon>
