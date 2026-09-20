<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exxfbpbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="exxfbpbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin2-filled" {...props}></Icon>
