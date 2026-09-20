<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gapcm6cdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gapcm6cdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-look-right" {...props}></Icon>
