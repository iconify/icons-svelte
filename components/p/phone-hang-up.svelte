<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilbmb7yhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilbmb7yhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:phone-hang-up" {...props}></Icon>
