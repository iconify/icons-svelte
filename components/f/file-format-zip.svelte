<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1z-b7k0t.css';
import '../../css/g/gnb4snbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1z-b7k0t"/><path class="gnb4snbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:file-format-zip" {...props}></Icon>
