<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz-ju9arh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz-ju9arh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:drill" {...props}></Icon>
