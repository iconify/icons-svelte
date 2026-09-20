<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbsus4b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbsus4b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-instagram-filled" {...props}></Icon>
