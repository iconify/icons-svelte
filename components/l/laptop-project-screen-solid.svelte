<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urhqt-mbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="urhqt-mbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:laptop-project-screen-solid" {...props}></Icon>
