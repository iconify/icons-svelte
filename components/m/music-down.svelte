<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz7gnccvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz7gnccvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-down" {...props}></Icon>
