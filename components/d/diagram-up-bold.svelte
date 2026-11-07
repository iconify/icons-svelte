<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umqx0z94l.css';
import '../../css/q/qbcs2nxgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umqx0z94l"/><path class="qbcs2nxgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diagram-up-bold" {...props}></Icon>
