<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvbo4bbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvbo4bbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cake-solid" {...props}></Icon>
