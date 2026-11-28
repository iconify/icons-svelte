<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn9vpqa0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn9vpqa0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-d20-solid" {...props}></Icon>
