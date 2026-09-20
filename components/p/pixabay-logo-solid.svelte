<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py0o4xekj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py0o4xekj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:pixabay-logo-solid" {...props}></Icon>
