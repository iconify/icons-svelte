<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf7f2ebgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf7f2ebgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:info-square-outline" {...props}></Icon>
