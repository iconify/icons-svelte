<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymf0v_b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymf0v_b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-big-small-fish-bold" {...props}></Icon>
