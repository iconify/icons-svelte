<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mssm-8b3t.css';
import '../../css/n/n5rw468eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mssm-8b3t"/><path class="n5rw468eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-left-stroke-square" {...props}></Icon>
