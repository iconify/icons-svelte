<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eisspdb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eisspdb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bamboo-gloss" {...props}></Icon>
