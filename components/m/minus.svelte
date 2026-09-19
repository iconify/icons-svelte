<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kztmef8on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kztmef8on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:minus" {...props}></Icon>
