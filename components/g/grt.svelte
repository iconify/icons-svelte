<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2t5gy2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd2t5gy2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:grt" {...props}></Icon>
