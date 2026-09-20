<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjna34s_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjna34s_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:medium-alt" {...props}></Icon>
