<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa1b8rrtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1b8rrtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-sharp" {...props}></Icon>
