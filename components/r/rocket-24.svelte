<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s53ifu8-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s53ifu8-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rocket-24" {...props}></Icon>
