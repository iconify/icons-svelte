<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmy2s3qlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kmy2s3qlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:neovim-wordmark" {...props}></Icon>
