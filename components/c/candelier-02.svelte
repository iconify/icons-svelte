<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sufajj_zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sufajj_zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:candelier-02" {...props}></Icon>
