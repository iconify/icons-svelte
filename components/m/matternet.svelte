<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sik-0kbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sik-0kbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:matternet" {...props}></Icon>
