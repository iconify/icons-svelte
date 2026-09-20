<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjosf6zur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjosf6zur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-cv-filled" {...props}></Icon>
