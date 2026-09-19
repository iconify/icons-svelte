<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0ddqacdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0ddqacdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:funicular-railway" {...props}></Icon>
