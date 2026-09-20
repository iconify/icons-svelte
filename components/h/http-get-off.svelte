<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9dn8cb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9dn8cb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-get-off" {...props}></Icon>
