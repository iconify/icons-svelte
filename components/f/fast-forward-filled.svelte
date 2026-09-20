<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri5tvzkkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri5tvzkkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fast-forward-filled" {...props}></Icon>
