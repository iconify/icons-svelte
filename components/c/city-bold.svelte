<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hltdeigko.css';
import '../../css/h/h5clszohm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hltdeigko"/><path clip-rule="evenodd" class="h5clszohm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:city-bold" {...props}></Icon>
