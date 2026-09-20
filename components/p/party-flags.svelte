<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l878qfblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l878qfblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:party-flags" {...props}></Icon>
