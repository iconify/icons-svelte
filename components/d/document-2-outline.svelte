<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esyxanb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esyxanb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-2-outline" {...props}></Icon>
