<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwrr2huym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwrr2huym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-pin" {...props}></Icon>
