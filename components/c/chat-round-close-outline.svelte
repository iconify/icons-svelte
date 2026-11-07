<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y20x_mi0c.css';
import '../../css/x/x9024bb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y20x_mi0c"/><path clip-rule="evenodd" class="x9024bb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-close-outline" {...props}></Icon>
