<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmg0r4s3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vmg0r4s3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pictures-folder-memories-remix" {...props}></Icon>
