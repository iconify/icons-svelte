<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_fa7rqxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_fa7rqxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:browser-x" {...props}></Icon>
