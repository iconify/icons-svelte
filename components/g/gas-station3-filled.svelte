<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5kcxvb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5kcxvb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gas-station3-filled" {...props}></Icon>
