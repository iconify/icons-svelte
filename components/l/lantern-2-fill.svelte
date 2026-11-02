<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crjj_4lqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crjj_4lqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lantern-2-fill" {...props}></Icon>
