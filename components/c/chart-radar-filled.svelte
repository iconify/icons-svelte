<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g98d97sgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g98d97sgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-radar-filled" {...props}></Icon>
