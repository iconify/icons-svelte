<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs7a71euu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hs7a71euu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lightning-fill" {...props}></Icon>
