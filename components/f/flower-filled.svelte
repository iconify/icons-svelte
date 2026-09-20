<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4hur1bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4hur1bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flower-filled" {...props}></Icon>
