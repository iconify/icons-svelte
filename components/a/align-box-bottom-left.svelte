<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etg_j4bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etg_j4bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-bottom-left" {...props}></Icon>
