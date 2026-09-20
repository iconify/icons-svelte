<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuyvh2sic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuyvh2sic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:archive-of-our-own" {...props}></Icon>
