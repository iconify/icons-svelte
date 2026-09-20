<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur4kl4b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur4kl4b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-douban" {...props}></Icon>
