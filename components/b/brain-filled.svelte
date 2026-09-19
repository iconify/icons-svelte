<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beb8cn1fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beb8cn1fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brain-filled" {...props}></Icon>
