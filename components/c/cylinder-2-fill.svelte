<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvf_dk-1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvf_dk-1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cylinder-2-fill" {...props}></Icon>
