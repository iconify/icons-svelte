<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8si76bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-6};
const content = `<path class="b8si76bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gamepad-retro-f" {...props}></Icon>
