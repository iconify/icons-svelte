<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqs0f2fsr.css';
import '../../css/u/uq4zqzbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqs0f2fsr"/><path class="uq4zqzbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-inner" {...props}></Icon>
