<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z12zi2w1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z12zi2w1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dice-6" {...props}></Icon>
