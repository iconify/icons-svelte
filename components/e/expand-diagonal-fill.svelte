<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkeom7bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkeom7bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-fill" {...props}></Icon>
