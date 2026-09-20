<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc2iix-ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc2iix-ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:bullhorn" {...props}></Icon>
