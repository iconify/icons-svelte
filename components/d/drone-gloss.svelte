<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc27ceb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc27ceb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drone-gloss" {...props}></Icon>
