<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv717kbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv717kbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-top-right" {...props}></Icon>
