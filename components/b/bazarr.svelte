<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo5dcenks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo5dcenks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bazarr" {...props}></Icon>
