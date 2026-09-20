<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdyowpb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdyowpb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:puppeteer" {...props}></Icon>
