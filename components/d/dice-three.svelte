<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0-k_j9dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0-k_j9dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dice-three" {...props}></Icon>
