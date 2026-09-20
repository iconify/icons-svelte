<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofufdvmay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofufdvmay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-6-fill" {...props}></Icon>
