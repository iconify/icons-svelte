<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox7kfwveo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox7kfwveo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:new-folder-solid" {...props}></Icon>
