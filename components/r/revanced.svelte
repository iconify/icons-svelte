<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q56e2tu1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q56e2tu1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:revanced" {...props}></Icon>
