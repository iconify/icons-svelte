<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feavt8iof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feavt8iof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cpu-gloss" {...props}></Icon>
