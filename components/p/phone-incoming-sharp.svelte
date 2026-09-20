<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7y1jabpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7y1jabpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-incoming-sharp" {...props}></Icon>
