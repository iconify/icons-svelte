<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rig9pzbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rig9pzbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:omega-duo" {...props}></Icon>
