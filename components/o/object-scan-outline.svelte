<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seofafb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="seofafb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:object-scan-outline" {...props}></Icon>
