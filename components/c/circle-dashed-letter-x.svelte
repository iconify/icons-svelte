<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpk2iddpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpk2iddpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-x" {...props}></Icon>
