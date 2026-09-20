<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko1yq89rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1yq89rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-charging" {...props}></Icon>
