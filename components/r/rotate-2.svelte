<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhslh1nsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhslh1nsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rotate-2" {...props}></Icon>
