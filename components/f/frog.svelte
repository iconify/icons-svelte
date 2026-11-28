<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aybc_5yie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aybc_5yie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:frog" {...props}></Icon>
