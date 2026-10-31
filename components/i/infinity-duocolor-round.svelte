<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejzu5je1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejzu5je1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:infinity-duocolor-round" {...props}></Icon>
