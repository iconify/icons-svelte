<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvoa-jc4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvoa-jc4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-line" {...props}></Icon>
