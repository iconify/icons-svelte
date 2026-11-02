<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6hpb75pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6hpb75pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:floating-dust-fill" {...props}></Icon>
