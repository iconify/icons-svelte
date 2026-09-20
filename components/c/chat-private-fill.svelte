<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o76epo28t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o76epo28t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-private-fill" {...props}></Icon>
