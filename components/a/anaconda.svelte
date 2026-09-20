<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tykev4j_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tykev4j_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:anaconda" {...props}></Icon>
