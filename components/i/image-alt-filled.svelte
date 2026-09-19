<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0p-lpbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y0p-lpbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-alt-filled" {...props}></Icon>
