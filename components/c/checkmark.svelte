<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlv30xa8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlv30xa8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:checkmark" {...props}></Icon>
