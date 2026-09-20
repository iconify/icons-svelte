<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nepsg6bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nepsg6bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-2-fill" {...props}></Icon>
