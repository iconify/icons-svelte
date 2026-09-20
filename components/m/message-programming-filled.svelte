<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf_b-v1zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf_b-v1zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-programming-filled" {...props}></Icon>
