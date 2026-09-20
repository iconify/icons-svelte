<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue_62kavg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue_62kavg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-drop-down-big" {...props}></Icon>
