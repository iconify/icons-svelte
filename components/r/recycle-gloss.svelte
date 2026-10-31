<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o59v4fb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o59v4fb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:recycle-gloss" {...props}></Icon>
