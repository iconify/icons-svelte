<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha6s8epuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha6s8epuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-folder" {...props}></Icon>
