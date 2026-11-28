<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4hegq5pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4hegq5pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cassette" {...props}></Icon>
