<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhcdpgb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhcdpgb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pills" {...props}></Icon>
