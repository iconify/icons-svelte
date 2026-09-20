<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzoxw91en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzoxw91en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-3-filled" {...props}></Icon>
