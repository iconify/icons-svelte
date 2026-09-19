<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyxc17_eu.css';
import '../../css/f/fg7w486wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gyxc17_eu"/><path class="fg7w486wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:microphone-outline" {...props}></Icon>
