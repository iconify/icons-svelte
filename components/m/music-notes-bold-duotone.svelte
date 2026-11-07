<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-i4kgtbw.css';
import '../../css/t/tsgsm7xry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-i4kgtbw"/><path class="tsgsm7xry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-notes-bold-duotone" {...props}></Icon>
