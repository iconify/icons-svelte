<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_xunb2ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_xunb2ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-check-sharp" {...props}></Icon>
