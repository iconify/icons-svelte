<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igvhj_65y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igvhj_65y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cmake" {...props}></Icon>
