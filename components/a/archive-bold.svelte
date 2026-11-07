<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x--eq7b-p.css';
import '../../css/s/s6dl6st5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x--eq7b-p"/><path class="s6dl6st5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-bold" {...props}></Icon>
