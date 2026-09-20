<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzj1rbc4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzj1rbc4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lightbulb" {...props}></Icon>
