<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buiyifbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buiyifbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-que-off" {...props}></Icon>
