<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi99i0bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gi99i0bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libera-chat-dark" {...props}></Icon>
