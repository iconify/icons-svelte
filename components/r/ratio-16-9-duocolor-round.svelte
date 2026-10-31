<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej9n68bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej9n68bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-16-9-duocolor-round" {...props}></Icon>
