<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5aytr1du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5aytr1du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:coins-filled" {...props}></Icon>
