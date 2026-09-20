<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfoobn32z.css';
import '../../css/m/mzwwu8c7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfoobn32z"/><path class="mzwwu8c7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-line" {...props}></Icon>
