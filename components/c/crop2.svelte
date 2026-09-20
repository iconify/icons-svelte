<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r29ui0i8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r29ui0i8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crop2" {...props}></Icon>
