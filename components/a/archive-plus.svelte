<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf2_6dygv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2_6dygv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:archive-plus" {...props}></Icon>
