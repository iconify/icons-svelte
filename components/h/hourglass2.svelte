<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-6f03bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-6f03bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hourglass2" {...props}></Icon>
