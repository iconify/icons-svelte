<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g119dzb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g119dzb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hand-stars-filled" {...props}></Icon>
