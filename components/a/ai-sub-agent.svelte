<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyaoj4kbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyaoj4kbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ai-sub-agent" {...props}></Icon>
