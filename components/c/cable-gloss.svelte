<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1jkbbbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1jkbbbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cable-gloss" {...props}></Icon>
