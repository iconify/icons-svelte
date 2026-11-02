<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdhh8zmon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdhh8zmon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-add-fill" {...props}></Icon>
