<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf96pub7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="wf96pub7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:picture-f" {...props}></Icon>
