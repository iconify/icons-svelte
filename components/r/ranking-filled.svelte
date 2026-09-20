<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu9gl7b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu9gl7b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ranking-filled" {...props}></Icon>
