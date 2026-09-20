<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o59h1ubic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o59h1ubic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:beach" {...props}></Icon>
