<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gycedn7lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gycedn7lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-fill" {...props}></Icon>
