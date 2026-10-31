<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy17h1biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy17h1biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrows-crossing-solid" {...props}></Icon>
