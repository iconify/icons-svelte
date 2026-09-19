<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdsp3nbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdsp3nbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:group-training" {...props}></Icon>
