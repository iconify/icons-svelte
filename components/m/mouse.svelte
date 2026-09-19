<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmdhmib0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmdhmib0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:mouse" {...props}></Icon>
