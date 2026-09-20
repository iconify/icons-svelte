<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg0sghp6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg0sghp6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:planet-off" {...props}></Icon>
