<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe509mbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe509mbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-close-round" {...props}></Icon>
