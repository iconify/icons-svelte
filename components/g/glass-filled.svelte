<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za6tz-qdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za6tz-qdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:glass-filled" {...props}></Icon>
