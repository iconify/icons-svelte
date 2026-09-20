<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlas83qsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlas83qsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-text-sharp" {...props}></Icon>
