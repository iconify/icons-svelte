<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e92x5sb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e92x5sb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:quotes" {...props}></Icon>
