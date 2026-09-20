<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plnj9kb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plnj9kb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:award-badge-star-bold" {...props}></Icon>
