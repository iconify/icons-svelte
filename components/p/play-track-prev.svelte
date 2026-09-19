<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8mcnhbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8mcnhbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-track-prev" {...props}></Icon>
