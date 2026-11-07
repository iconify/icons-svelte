<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl1511bqd.css';
import '../../css/s/s6dl6st5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl1511bqd"/><path class="s6dl6st5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-check-bold" {...props}></Icon>
