<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbpvwn_cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbpvwn_cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-bolt" {...props}></Icon>
