<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uul-3l39q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uul-3l39q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:profile-filled" {...props}></Icon>
