<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-03f5vrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-03f5vrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clock-check-gloss" {...props}></Icon>
