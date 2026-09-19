<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tod_2acqn.css';
import '../../css/h/hj1bo3bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tod_2acqn"/><path class="hj1bo3bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-wide-narrow-filled" {...props}></Icon>
