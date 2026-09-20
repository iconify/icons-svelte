<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eli2exp3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eli2exp3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:monitor3" {...props}></Icon>
