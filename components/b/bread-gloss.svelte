<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykj6llbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykj6llbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bread-gloss" {...props}></Icon>
