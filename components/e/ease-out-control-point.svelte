<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyhob48_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyhob48_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-out-control-point" {...props}></Icon>
