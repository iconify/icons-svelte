<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da-21i6_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da-21i6_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:moon-line" {...props}></Icon>
