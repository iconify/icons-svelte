<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9-fgdbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9-fgdbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-template-24" {...props}></Icon>
