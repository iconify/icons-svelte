<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksuggwa2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksuggwa2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:moon-star" {...props}></Icon>
