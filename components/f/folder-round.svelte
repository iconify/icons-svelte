<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3i9qpgha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3i9qpgha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-round" {...props}></Icon>
