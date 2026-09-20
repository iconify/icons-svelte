<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndzc9_vnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndzc9_vnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exclude-fill" {...props}></Icon>
