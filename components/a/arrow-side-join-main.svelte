<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjcgnuboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjcgnuboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-side-join-main" {...props}></Icon>
