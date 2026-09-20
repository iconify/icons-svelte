<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aawv7kwfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aawv7kwfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:openai" {...props}></Icon>
