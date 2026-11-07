<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue3ui5iyp.css';
import '../../css/h/haz-fbj8x.css';
import '../../css/w/wryd348yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue3ui5iyp"/><path class="haz-fbj8x"/><path class="wryd348yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diskette-bold-duotone" {...props}></Icon>
