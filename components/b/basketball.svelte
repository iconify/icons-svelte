<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmi3pacbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmi3pacbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:basketball" {...props}></Icon>
