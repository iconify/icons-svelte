<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahx8d0d9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahx8d0d9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:person-x" {...props}></Icon>
