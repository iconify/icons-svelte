<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvfc_ab5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvfc_ab5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid6-filled" {...props}></Icon>
