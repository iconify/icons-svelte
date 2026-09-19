<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfyw0bf2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfyw0bf2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:capture-filled" {...props}></Icon>
