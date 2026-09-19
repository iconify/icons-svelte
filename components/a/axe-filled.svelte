<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz39kfbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz39kfbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:axe-filled" {...props}></Icon>
