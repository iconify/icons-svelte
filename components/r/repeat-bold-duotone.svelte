<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6iijhcww.css';
import '../../css/x/xq74wrb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6iijhcww"/><path class="xq74wrb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-bold-duotone" {...props}></Icon>
