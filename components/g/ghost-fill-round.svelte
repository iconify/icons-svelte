<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s980kpblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s980kpblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ghost-fill-round" {...props}></Icon>
