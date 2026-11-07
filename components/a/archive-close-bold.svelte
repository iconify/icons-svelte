<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfo7vac9f.css';
import '../../css/s/s6dl6st5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfo7vac9f"/><path class="s6dl6st5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-close-bold" {...props}></Icon>
