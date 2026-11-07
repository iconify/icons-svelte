<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-mexebzb.css';
import '../../css/n/nbkh3ubia.css';
import '../../css/a/abgizhdkn.css';
import '../../css/b/bvct38blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-mexebzb"/><path class="nbkh3ubia"/><path class="abgizhdkn"/><path class="bvct38blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-bold" {...props}></Icon>
