<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4cm-_b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4cm-_b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-i" {...props}></Icon>
