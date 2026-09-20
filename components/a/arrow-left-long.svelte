<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrcfogc1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrcfogc1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrow-left-long" {...props}></Icon>
