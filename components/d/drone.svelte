<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/som248tye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="som248tye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:drone" {...props}></Icon>
