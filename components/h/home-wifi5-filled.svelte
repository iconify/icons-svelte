<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha6m8geft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha6m8geft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-wifi5-filled" {...props}></Icon>
