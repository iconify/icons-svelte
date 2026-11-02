<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsldembvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsldembvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fishing-rod-fill" {...props}></Icon>
