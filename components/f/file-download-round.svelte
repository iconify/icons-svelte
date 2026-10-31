<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn44wv8re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn44wv8re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-download-round" {...props}></Icon>
