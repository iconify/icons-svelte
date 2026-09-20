<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km2deyk9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km2deyk9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:divider-1" {...props}></Icon>
