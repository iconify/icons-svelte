<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7_3zbcie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7_3zbcie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bread" {...props}></Icon>
