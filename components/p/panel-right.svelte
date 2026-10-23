<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-v_a5bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-v_a5bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-right" {...props}></Icon>
