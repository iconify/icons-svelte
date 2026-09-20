<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmd_69bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmd_69bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:powervirtualagents" {...props}></Icon>
