<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1ap0cjsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1ap0cjsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:comment" {...props}></Icon>
