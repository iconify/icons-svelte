<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eurm6x-rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eurm6x-rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:artboard-off" {...props}></Icon>
