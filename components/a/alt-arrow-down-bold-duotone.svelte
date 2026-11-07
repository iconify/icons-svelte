<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4fzscdmy.css';
import '../../css/f/fjjhjc8fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4fzscdmy"/><path class="fjjhjc8fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-down-bold-duotone" {...props}></Icon>
