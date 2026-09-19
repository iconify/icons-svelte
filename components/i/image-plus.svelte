<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvz3gdbus.css';
import '../../css/m/mz1hr1bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvz3gdbus"/><path class="mz1hr1bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-plus" {...props}></Icon>
