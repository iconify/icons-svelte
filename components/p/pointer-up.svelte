<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwc74bb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwc74bb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-up" {...props}></Icon>
