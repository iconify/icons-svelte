<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3sutw5kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3sutw5kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:move-to-start-24" {...props}></Icon>
