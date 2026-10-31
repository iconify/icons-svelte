<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf3glqpje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf3glqpje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alert-circle-gloss" {...props}></Icon>
