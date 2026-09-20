<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8vj0cb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8vj0cb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:here" {...props}></Icon>
