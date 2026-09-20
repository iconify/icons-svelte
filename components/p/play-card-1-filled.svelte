<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5p-dwbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5p-dwbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-1-filled" {...props}></Icon>
