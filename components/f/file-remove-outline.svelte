<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_lz50_l.css';
import '../../css/w/wih7av0dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_lz50_l"/><path class="wih7av0dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:file-remove-outline" {...props}></Icon>
