<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5sk6zb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5sk6zb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mandarin-orange-gloss" {...props}></Icon>
