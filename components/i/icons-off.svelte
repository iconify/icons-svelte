<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsn7bex_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsn7bex_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:icons-off" {...props}></Icon>
