<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr39v2-gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr39v2-gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fridge" {...props}></Icon>
