<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc1fkebdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc1fkebdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-snow" {...props}></Icon>
