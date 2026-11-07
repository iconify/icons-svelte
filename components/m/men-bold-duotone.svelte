<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukbct-jgm.css';
import '../../css/n/n6fnwhbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="ukbct-jgm"/><path class="n6fnwhbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:men-bold-duotone" {...props}></Icon>
