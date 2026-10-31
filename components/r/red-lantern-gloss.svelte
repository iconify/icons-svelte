<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr0bi7biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr0bi7biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:red-lantern-gloss" {...props}></Icon>
