<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bizeh-ogo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bizeh-ogo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cooldown-fill" {...props}></Icon>
