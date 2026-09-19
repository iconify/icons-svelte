<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc-660lro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-660lro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:folder" {...props}></Icon>
