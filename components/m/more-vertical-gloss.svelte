<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoqc6bbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoqc6bbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-vertical-gloss" {...props}></Icon>
