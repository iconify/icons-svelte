<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm-fdvb-j.css';
import '../../css/s/s6dl6st5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-fdvb-j"/><path class="s6dl6st5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-bold" {...props}></Icon>
