<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si728y-uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si728y-uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-caret-right-filled" {...props}></Icon>
