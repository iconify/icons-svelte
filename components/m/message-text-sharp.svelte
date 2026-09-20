<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anks12bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anks12bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-text-sharp" {...props}></Icon>
