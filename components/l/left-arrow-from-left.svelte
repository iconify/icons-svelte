<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1pvndapw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1pvndapw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:left-arrow-from-left" {...props}></Icon>
