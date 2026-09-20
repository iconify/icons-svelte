<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dahkt0btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dahkt0btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:live-photo-filled" {...props}></Icon>
