<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9h_shb9i.css';
import '../../css/u/uz30z7t_j.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9h_shb9i"/><path clip-rule="evenodd" class="uz30z7t_j"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-cog-bold" {...props}></Icon>
