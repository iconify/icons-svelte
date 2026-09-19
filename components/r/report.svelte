<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kscenjt4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kscenjt4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:report" {...props}></Icon>
