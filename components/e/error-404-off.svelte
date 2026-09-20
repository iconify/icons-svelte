<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eag81cn8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eag81cn8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:error-404-off" {...props}></Icon>
