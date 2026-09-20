<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_jcbfb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_jcbfb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pennant-filled" {...props}></Icon>
