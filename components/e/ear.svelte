<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2mnqpber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2mnqpber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ear" {...props}></Icon>
