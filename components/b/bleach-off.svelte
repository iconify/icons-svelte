<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezekt3baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezekt3baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bleach-off" {...props}></Icon>
