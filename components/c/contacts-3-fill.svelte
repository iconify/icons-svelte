<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8b5ddb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8b5ddb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-3-fill" {...props}></Icon>
