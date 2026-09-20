<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af466gpom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af466gpom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exclamation-mark-off" {...props}></Icon>
