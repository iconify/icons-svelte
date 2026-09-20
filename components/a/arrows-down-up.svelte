<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8p8ekymi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8p8ekymi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-down-up" {...props}></Icon>
