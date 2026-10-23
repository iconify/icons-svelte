<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9_c1hoau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9_c1hoau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:key" {...props}></Icon>
