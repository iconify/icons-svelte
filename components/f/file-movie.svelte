<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7gmfrjki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7gmfrjki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:file-movie" {...props}></Icon>
