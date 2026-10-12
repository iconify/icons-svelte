<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1g9m8u7c.css';
import '../../css/t/tm09_9c4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1g9m8u7c"/><path clip-rule="evenodd" class="tm09_9c4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:briefcase-conveyor-belt-filled" {...props}></Icon>
