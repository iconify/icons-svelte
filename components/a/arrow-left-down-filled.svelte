<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsv90912w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsv90912w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left-down-filled" {...props}></Icon>
