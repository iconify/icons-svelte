<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgv2w6bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgv2w6bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:blank-fill" {...props}></Icon>
