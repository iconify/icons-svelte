<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmkxam5pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmkxam5pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:banana" {...props}></Icon>
