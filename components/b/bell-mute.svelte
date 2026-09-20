<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvs0_tbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvs0_tbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bell-mute" {...props}></Icon>
