<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-dh3gkit.css';
import '../../css/d/d8g489bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-dh3gkit"/><path class="d8g489bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-cog-filled" {...props}></Icon>
