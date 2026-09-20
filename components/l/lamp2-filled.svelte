<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb_qf6ies.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb_qf6ies"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lamp2-filled" {...props}></Icon>
