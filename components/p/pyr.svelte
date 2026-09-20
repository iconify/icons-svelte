<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cis9tc4cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cis9tc4cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pyr" {...props}></Icon>
