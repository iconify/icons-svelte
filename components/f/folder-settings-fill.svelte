<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utw1xcbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utw1xcbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-settings-fill" {...props}></Icon>
