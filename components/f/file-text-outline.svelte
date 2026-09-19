<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf5_33bau.css';
import '../../css/n/nx_lz50_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf5_33bau"/><path class="nx_lz50_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:file-text-outline" {...props}></Icon>
