<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-f8xob-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-f8xob-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-bolt-bold" {...props}></Icon>
