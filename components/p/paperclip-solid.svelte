<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glkby61tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glkby61tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:paperclip-solid" {...props}></Icon>
