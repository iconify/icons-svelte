<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c18qyszxk.css';
import '../../css/c/cwaoh8bpd.css';
import '../../css/n/nrw-6wbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c18qyszxk"/><path class="cwaoh8bpd"/><path class="nrw-6wbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:puppeteer" {...props}></Icon>
