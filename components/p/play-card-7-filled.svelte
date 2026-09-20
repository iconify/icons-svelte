<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz9uk5bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz9uk5bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-7-filled" {...props}></Icon>
