<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfax0i5fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfax0i5fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mouse" {...props}></Icon>
