<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0eo5abtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0eo5abtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-off" {...props}></Icon>
