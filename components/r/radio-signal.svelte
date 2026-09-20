<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7kvxpb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7kvxpb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:radio-signal" {...props}></Icon>
