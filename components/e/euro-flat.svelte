<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo7lvo_4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fo7lvo_4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:euro-flat" {...props}></Icon>
