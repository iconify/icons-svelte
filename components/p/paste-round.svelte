<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r04mx-bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r04mx-bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paste-round" {...props}></Icon>
