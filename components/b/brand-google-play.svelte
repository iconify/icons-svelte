<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smz5hpcph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smz5hpcph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-google-play" {...props}></Icon>
