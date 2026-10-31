<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmbafvbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmbafvbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ambulance-fill-round" {...props}></Icon>
