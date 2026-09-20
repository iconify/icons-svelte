<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfujh6bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfujh6bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:coffee" {...props}></Icon>
