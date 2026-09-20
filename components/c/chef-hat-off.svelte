<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrmpk4ctg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrmpk4ctg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chef-hat-off" {...props}></Icon>
