<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n25yeq5ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n25yeq5ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cut" {...props}></Icon>
