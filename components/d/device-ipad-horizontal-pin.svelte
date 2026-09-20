<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuagr4bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuagr4bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-pin" {...props}></Icon>
