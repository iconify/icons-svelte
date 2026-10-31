<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cge5m7bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cge5m7bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-check-round" {...props}></Icon>
